# Function: <code>sp_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0ea0)
Location: mm/mempolicy.c:2224
Inline: False
Direct callers:
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff811e0ea0-ffffffff811e0ecd: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ff870)
Location: mm/mempolicy.c:2245
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff811ff870-ffffffff811ff89d: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81210e90)
Location: mm/mempolicy.c:2239
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff81210e90-ffffffff81210ebd: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121c810)
Location: mm/mempolicy.c:2141
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff8121c810-ffffffff8121c83d: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812379c0)
Location: mm/mempolicy.c:2203
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff812379c0-ffffffff812379ed: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125ae90)
Location: mm/mempolicy.c:2263
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff8125ae90-ffffffff8125aebd: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126f650)
Location: mm/mempolicy.c:2302
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff8126f650-ffffffff8126f67d: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128ac30)
Location: mm/mempolicy.c:2323
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff8128ac30-ffffffff8128ac5f: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a7a0)
Location: mm/mempolicy.c:2362
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff8129a7a0-ffffffff8129a7cf: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d0704)
Location: mm/mempolicy.c:2461
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dc224)
Location: mm/mempolicy.c:2436
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3ac1)
Location: mm/mempolicy.c:2441
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132ada1)
Location: mm/mempolicy.c:2358
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a780)
Location: mm/mempolicy.c:2534
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a776)
Location: mm/mempolicy.c:2549
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144dcec)
Location: mm/mempolicy.c:2560
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81487bb2)
Location: mm/mempolicy.c:2460
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
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
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010339308)
Location: mm/mempolicy.c:2362
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffff800010339308-ffff800010339348: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413b70)
Location: mm/mempolicy.c:2362
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
c000000000413b70-c000000000413bcc: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292d80)
Location: mm/mempolicy.c:2362
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff81292d80-ffffffff81292daf: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284990)
Location: mm/mempolicy.c:2362
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff81284990-ffffffff812849bf: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290b90)
Location: mm/mempolicy.c:2362
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff81290b90-ffffffff81290bbf: sp_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sp_free(struct sp_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a09c0)
Location: mm/mempolicy.c:2362
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:sp_delete
```
**Symbols:**

```
ffffffff812a09c0-ffffffff812a09ef: sp_free (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
