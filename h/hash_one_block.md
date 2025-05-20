# Function: <code>hash_one_block</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hash_one_block(struct inode *inode, const struct merkle_tree_params *params, struct block_buffer *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:22
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff8153b570-ffffffff8153b610: hash_one_block (STB_LOCAL)
ffffffff820ea81b-ffffffff820ea830: hash_one_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hash_one_block(struct inode *inode, const struct merkle_tree_params *params, struct block_buffer *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:22
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff81570850-ffffffff815708f0: hash_one_block (STB_LOCAL)
ffffffff821c74c9-ffffffff821c74de: hash_one_block.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
