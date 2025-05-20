# Function: <code>jbd2_journal_revoke</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff812ed8d0)
Location: fs/jbd2/revoke.c:324
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff812ed8d0-ffffffff812eda03: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8131b220)
Location: fs/jbd2/revoke.c:324
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff8131b220-ffffffff8131b34a: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81331210)
Location: fs/jbd2/revoke.c:325
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81331210-ffffffff8133133a: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81346170)
Location: fs/jbd2/revoke.c:325
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81346170-ffffffff8134629f: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8136a800)
Location: fs/jbd2/revoke.c:325
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff8136a800-ffffffff8136a92f: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:318
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff813995ba-ffffffff81399622: jbd2_journal_revoke.cold.14 (STB_LOCAL)
ffffffff81398f80-ffffffff81399069: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:318
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff813b232a-ffffffff813b2392: jbd2_journal_revoke.cold.14 (STB_LOCAL)
ffffffff813b1cf0-ffffffff813b1dd9: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff813dc99a-ffffffff813dca02: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff813dc340-ffffffff813dc431: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff813f69da-ffffffff813f6a42: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff813f6390-ffffffff813f6481: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81443e4a-ffffffff81443ead: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff814438d0-ffffffff81443a11: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81becf4b-ffffffff81becfae: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff8145f9b0-ffffffff8145faf1: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81bdf032-ffffffff81bdf095: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff814650a0-ffffffff814651de: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81cce8cf-ffffffff81cce932: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff814baa20-ffffffff814bab5e: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81e81970-ffffffff81e819ce: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff815448d0-ffffffff815449ff: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff815e3980)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff815e3980-ffffffff815e3afd: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8161b140)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff8161b140-ffffffff8161b2bd: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81654060)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81654060-ffffffff816541dd: jbd2_journal_revoke (STB_GLOBAL)
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
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffff8000104d23a8)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffff8000104d23a8-ffff8000104d2530: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (c0694ae8)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
c0694ae8-c0694c70: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (c00000000060ba90)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
c00000000060ba90-c00000000060bcdc: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffe00034948e)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffe00034948e-ffffffe0003495de: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff813eefba-ffffffff813ef022: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff813ee970-ffffffff813eea61: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff813dfa3a-ffffffff813dfaa2: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff813df3f0-ffffffff813df4e1: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff813ec33a-ffffffff813ec3a2: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff813ebcf0-ffffffff813ebde1: jbd2_journal_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_revoke(handle_t *handle, long long unsigned int blocknr, struct buffer_head *bh_in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:326
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff81401cda-ffffffff81401d42: jbd2_journal_revoke.cold (STB_LOCAL)
ffffffff814016a0-ffffffff8140178c: jbd2_journal_revoke (STB_GLOBAL)
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
