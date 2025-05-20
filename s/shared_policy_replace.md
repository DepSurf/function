# Function: <code>shared_policy_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e2e9c)
Location: mm/mempolicy.c:2354
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812018cf)
Location: mm/mempolicy.c:2393
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812133bf)
Location: mm/mempolicy.c:2387
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121e6e4)
Location: mm/mempolicy.c:2289
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
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
In mm/mempolicy.c (ffffffff81239904)
Location: mm/mempolicy.c:2346
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
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
In mm/mempolicy.c (ffffffff8125cebb)
Location: mm/mempolicy.c:2406
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81271797)
Location: mm/mempolicy.c:2445
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128cdb0)
Location: mm/mempolicy.c:2466
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129c9e0)
Location: mm/mempolicy.c:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cd840)
Location: mm/mempolicy.c:2604
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff812cd840-ffffffff812cd9f9: shared_policy_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d8770)
Location: mm/mempolicy.c:2579
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff812d8770-ffffffff812d8929: shared_policy_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dfe00)
Location: mm/mempolicy.c:2587
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff812dfe00-ffffffff812dffb9: shared_policy_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81327340)
Location: mm/mempolicy.c:2508
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff81327340-ffffffff813274f9: shared_policy_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813963d0)
Location: mm/mempolicy.c:2684
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff813963d0-ffffffff813965bb: shared_policy_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81415ce0)
Location: mm/mempolicy.c:2699
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff81415ce0-ffffffff81415ecb: shared_policy_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814492c0)
Location: mm/mempolicy.c:2710
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff814492c0-ffffffff814494ab: shared_policy_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shared_policy_replace(struct shared_policy *sp, long unsigned int start, long unsigned int end, struct sp_node *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81482c30)
Location: mm/mempolicy.c:2609
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff81482c30-ffffffff81482f0f: shared_policy_replace (STB_LOCAL)
```
</details>
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
In mm/mempolicy.c (ffff80001033b99c)
Location: mm/mempolicy.c:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c0000000004167f4)
Location: mm/mempolicy.c:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294fc0)
Location: mm/mempolicy.c:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
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
In mm/mempolicy.c (ffffffff81286bd0)
Location: mm/mempolicy.c:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
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
In mm/mempolicy.c (ffffffff81292dd0)
Location: mm/mempolicy.c:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
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
In mm/mempolicy.c (ffffffff812a2bc3)
Location: mm/mempolicy.c:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
