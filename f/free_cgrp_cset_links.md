# Function: <code>free_cgrp_cset_links</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81112030)
Location: kernel/cgroup.c:940
Inline: False
Direct callers:
  - kernel/cgroup.c:allocate_cgrp_cset_links
  - kernel/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff81112030-ffffffff81112099: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81119750)
Location: kernel/cgroup.c:985
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff81119750-ffffffff811197bf: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81121230)
Location: kernel/cgroup.c:988
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff81121230-ffffffff8112129f: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81121980)
Location: kernel/cgroup/cgroup.c:881
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff81121980-ffffffff811219ef: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112d030)
Location: kernel/cgroup/cgroup.c:1026
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff8112d030-ffffffff8112d09f: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113b6d0)
Location: kernel/cgroup/cgroup.c:1029
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff8113b6d0-ffffffff8113b73f: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81146d90)
Location: kernel/cgroup/cgroup.c:1064
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff81146d90-ffffffff81146dff: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151f60)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff81151f60-ffffffff81151fcf: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115dbb0)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff8115dbb0-ffffffff8115dc1f: free_cgrp_cset_links (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff81175698)
Location: kernel/cgroup/cgroup.c:1096
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
In kernel/cgroup/cgroup.c (ffffffff81172348)
Location: kernel/cgroup/cgroup.c:1093
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
In kernel/cgroup/cgroup.c (ffffffff81172e88)
Location: kernel/cgroup/cgroup.c:1093
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
In kernel/cgroup/cgroup.c (ffffffff81199d08)
Location: kernel/cgroup/cgroup.c:1124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
In kernel/cgroup/cgroup.c (ffffffff811c9eb0)
Location: kernel/cgroup/cgroup.c:1126
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
In kernel/cgroup/cgroup.c (ffffffff8120d050)
Location: kernel/cgroup/cgroup.c:1131
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
In kernel/cgroup/cgroup.c (ffffffff81222a40)
Location: kernel/cgroup/cgroup.c:1115
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
In kernel/cgroup/cgroup.c (ffffffff8123a730)
Location: kernel/cgroup/cgroup.c:1095
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
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
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101ce228)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffff8000101ce228-ffff8000101ce2a4: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041185c)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
c041185c-c04118c4: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000237ec0)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
c000000000237ec0-c000000000237f84: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000148c26)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffe000148c26-ffffffe000148c92: free_cgrp_cset_links (STB_LOCAL)
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
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811561d0)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff811561d0-ffffffff8115623f: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811494f0)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff811494f0-ffffffff8114955f: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81153fa0)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff81153fa0-ffffffff8115400f: free_cgrp_cset_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_cgrp_cset_links(struct list_head *links_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81160ea0)
Location: kernel/cgroup/cgroup.c:1104
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
```
**Symbols:**

```
ffffffff81160ea0-ffffffff81160f0f: free_cgrp_cset_links (STB_LOCAL)
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
