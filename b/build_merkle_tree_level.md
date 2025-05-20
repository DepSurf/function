# Function: <code>build_merkle_tree_level</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff8134f658)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree_level(struct file *filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params *params, u8 *pending_hashes, struct ahash_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:44
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff81395d30-ffffffff813960d9: build_merkle_tree_level (STB_LOCAL)
ffffffff81396791-ffffffff81396809: build_merkle_tree_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree_level(struct file *filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params *params, u8 *pending_hashes, struct ahash_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:44
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff813a7a50-ffffffff813a7df6: build_merkle_tree_level (STB_LOCAL)
ffffffff81beb328-ffffffff81beb3a0: build_merkle_tree_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree_level(struct file *filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params *params, u8 *pending_hashes, struct ahash_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:44
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff813aeab0-ffffffff813aee58: build_merkle_tree_level (STB_LOCAL)
ffffffff81bdd37f-ffffffff81bdd3f7: build_merkle_tree_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree_level(struct file *filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params *params, u8 *pending_hashes, struct ahash_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:44
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff813fe650-ffffffff813fe9f8: build_merkle_tree_level (STB_LOCAL)
ffffffff81cc6c4c-ffffffff81cc6cc4: build_merkle_tree_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree_level(struct file *filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params *params, u8 *pending_hashes, struct ahash_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:43
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff81472160-ffffffff81472577: build_merkle_tree_level (STB_LOCAL)
ffffffff81e79191-ffffffff81e7920b: build_merkle_tree_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int build_merkle_tree_level(struct file *filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params *params, u8 *pending_hashes, struct ahash_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81503c00)
Location: fs/verity/enable.c:43
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
```
**Symbols:**

```
ffffffff81503c00-ffffffff81504246: build_merkle_tree_level (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffff80001041104c)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (c05dd668)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (c00000000051eb80)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffe0002b94be)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81347c38)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81338918)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81345708)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff813589e8)
Location: fs/verity/enable.c:16
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
