# Function: <code>idr_alloc_u32</code>

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
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819ced30)
Location: lib/idr.c:34
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_create
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff819ced30-ffffffff819cee11: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a081f0)
Location: lib/idr.c:32
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81a081f0-ffffffff81a082b2: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77b40)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81a77b40-ffffffff81a77c05: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaef30)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81aaef30-ffffffff81aaeff5: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e8c60)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff815e8c60-ffffffff815e8d25: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160dd10)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff8160dd10-ffffffff8160ddd5: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1460)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff815f1460-ffffffff815f1525: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e5d0)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff8165e5d0-ffffffff8165e695: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81777dc0)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff81777dc0-ffffffff81777eab: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020ac0)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff82020ac0-ffffffff82020bab: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0ae0)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff820a0ae0-ffffffff820a0bcb: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178ac0)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff82178ac0-ffffffff82178bab: idr_alloc_u32 (STB_GLOBAL)
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
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88718)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffff800010d88718-ffff800010d88800: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e8357c)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
c0e8357c-c0e83698: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec8e30)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
c000000000ec8e30-c000000000ec8f5c: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2736)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffe0008b2736-ffffffe0008b27e2: idr_alloc_u32 (STB_GLOBAL)
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
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4dd80)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81a4dd80-ffffffff81a4de45: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0ae70)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81a0ae70-ffffffff81a0af35: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba170)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81aba170-ffffffff81aba235: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr *idr, void *ptr, u32 *nextid, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac65c0)
Location: lib/idr.c:33
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81ac65c0-ffffffff81ac6685: idr_alloc_u32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
