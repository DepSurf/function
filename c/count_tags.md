# Function: <code>count_tags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff812eb7b0)
Location: fs/jbd2/recovery.c:201
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff812eb7b0-ffffffff812eb889: count_tags.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff813192c0)
Location: fs/jbd2/recovery.c:200
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813192c0-ffffffff8131939a: count_tags.isra.6 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff8132f2b0)
Location: fs/jbd2/recovery.c:200
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff8132f2b0-ffffffff8132f38a: count_tags.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81344370)
Location: fs/jbd2/recovery.c:200
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81344370-ffffffff81344413: count_tags.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81368a10)
Location: fs/jbd2/recovery.c:200
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81368a10-ffffffff81368ab3: count_tags.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81397250)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81397250-ffffffff813972ec: count_tags.isra.8 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813aff80)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813aff80-ffffffff813b001c: count_tags.isra.8 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813da510)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813da510-ffffffff813da5b1: count_tags.isra.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813f4560)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813f4560-ffffffff813f4601: count_tags.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81441830)
Location: fs/jbd2/recovery.c:197
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
**Symbols:**

```
ffffffff81441830-ffffffff814418d4: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff8145da20)
Location: fs/jbd2/recovery.c:196
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
**Symbols:**

```
ffffffff8145da20-ffffffff8145dac4: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81463330)
Location: fs/jbd2/recovery.c:196
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81463330-ffffffff814633cc: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff814b8940)
Location: fs/jbd2/recovery.c:196
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff814b8940-ffffffff814b8a1d: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff815424c0)
Location: fs/jbd2/recovery.c:196
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff815424c0-ffffffff815425c6: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff815e11e0)
Location: fs/jbd2/recovery.c:201
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff815e11e0-ffffffff815e12e6: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81618ad0)
Location: fs/jbd2/recovery.c:202
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81618ad0-ffffffff81618bd5: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81651a50)
Location: fs/jbd2/recovery.c:202
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81651a50-ffffffff81651b55: count_tags (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffff8000104cfeb8)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffff8000104cfeb8-ffff8000104cff78: count_tags.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int count_tags(journal_t *journal, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (c069297c)
Location: fs/jbd2/recovery.c:197
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
c069297c-c0692a50: count_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (c000000000608e30)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
c000000000608e30-c000000000608f38: count_tags.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffe0003474c8)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffe0003474c8-ffffffe000347560: count_tags.isra.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813ecb40)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813ecb40-ffffffff813ecbe1: count_tags.isra.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813dd5c0)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813dd5c0-ffffffff813dd661: count_tags.isra.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813e9ec0)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813e9ec0-ffffffff813e9f61: count_tags.isra.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813ff800)
Location: fs/jbd2/recovery.c:197
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813ff800-ffffffff813ff8a1: count_tags.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
