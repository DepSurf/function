# Function: <code>tcf_get_next_chain</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195ea40)
Location: net/sched/cls_api.c:1062
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_tclass
  - net/sched/sch_api.c:tc_bind_tclass
```
**Symbols:**

```
ffffffff8195ea40-ffffffff8195ea72: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81995320)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81995320-ffffffff81995352: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6f0f9)
Location: net/sched/cls_api.c:939
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81a6e040-ffffffff81a6e072: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a77ad5)
Location: net/sched/cls_api.c:941
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81a76a10-ffffffff81a76a42: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a60c65)
Location: net/sched/cls_api.c:941
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81a5e910-ffffffff81a5e942: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b19ed5)
Location: net/sched/cls_api.c:942
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81b17ae0-ffffffff81b17b12: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca0abb)
Location: net/sched/cls_api.c:959
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81c9f950-ffffffff81c9f98a: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5caeb)
Location: net/sched/cls_api.c:961
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81e5bbf0-ffffffff81e5bc2a: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb9692)
Location: net/sched/cls_api.c:1066
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81eb83f0-ffffffff81eb842a: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7c7ea)
Location: net/sched/cls_api.c:1068
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81f7b4c0-ffffffff81f7b4fa: tcf_get_next_chain (STB_GLOBAL)
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
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c41ef8)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffff800010c41ef8-ffff800010c41f48: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53cb0)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
c0d53cb0-c0d53cf0: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3de60)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
c000000000d3de60-c000000000d3dec4: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b1758)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffe0007b1758-ffffffe0007b179e: tcf_get_next_chain (STB_GLOBAL)
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
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81935190)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81935190-ffffffff819351c2: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eec90)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff818eec90-ffffffff818eecc2: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81986320)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81986320-ffffffff81986352: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct tcf_chain *tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9320)
Location: net/sched/cls_api.c:976
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff819a9320-ffffffff819a9352: tcf_get_next_chain (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
