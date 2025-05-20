# Function: <code>longest_prefix_match</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8119e6c4)
Location: kernel/bpf/lpm_trie.c:165
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ae105)
Location: kernel/bpf/lpm_trie.c:165
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811c5de2)
Location: kernel/bpf/lpm_trie.c:165
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811d71e0)
Location: kernel/bpf/lpm_trie.c:167
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff811d71e0-ffffffff811d72f8: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ebbb0)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff811ebbb0-ffffffff811ebcbd: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811f8310)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff811f8310-ffffffff811f841d: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8121c200)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff8121c200-ffffffff8121c307: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8121f110)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff8121f110-ffffffff8121f217: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81222ba0)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff81222ba0-ffffffff81222ca1: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8125a950)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff8125a950-ffffffff8125aa51: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff812a3a90)
Location: kernel/bpf/lpm_trie.c:165
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff812a3a90-ffffffff812a3c19: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81301690)
Location: kernel/bpf/lpm_trie.c:165
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff81301690-ffffffff81301819: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff813301d0)
Location: kernel/bpf/lpm_trie.c:165
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff813301d0-ffffffff813303cf: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff813546f0)
Location: kernel/bpf/lpm_trie.c:165
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff813546f0-ffffffff813548fc: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffff80001027d608)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffff80001027d608-ffff80001027d7c8: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t longest_prefix_match(const struct lpm_trie *trie, const struct lpm_trie_node *node, const struct bpf_lpm_trie_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (c04aee48)
Location: kernel/bpf/lpm_trie.c:164
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
c04aee48-c04aef64: longest_prefix_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t longest_prefix_match(const struct lpm_trie *trie, const struct lpm_trie_node *node, const struct bpf_lpm_trie_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (c000000000326ff0)
Location: kernel/bpf/lpm_trie.c:164
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
c000000000326ff0-c000000000327198: longest_prefix_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t longest_prefix_match(const struct lpm_trie *trie, const struct lpm_trie_node *node, const struct bpf_lpm_trie_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffe0001b48b6)
Location: kernel/bpf/lpm_trie.c:164
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffe0001b48b6-ffffffe0001b4ab8: longest_prefix_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811f0930)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff811f0930-ffffffff811f0a3d: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811e3680)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff811e3680-ffffffff811e378d: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ee700)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff811ee700-ffffffff811ee80d: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811fcbd0)
Location: kernel/bpf/lpm_trie.c:164
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
**Symbols:**

```
ffffffff811fcbd0-ffffffff811fccdd: longest_prefix_match.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
